<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi3l8-bkb.css';
import '../../css/r/rpkswgq3h.css';
import '../../css/d/dujhcdcuw.css';
import '../../css/r/rgq401bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi3l8-bkb"/><circle class="rpkswgq3h"/><circle class="dujhcdcuw"/><circle class="rgq401bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-alt-3" {...props}></Icon>
