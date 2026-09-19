<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-_nkce5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-_nkce5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-rounded-minus" {...props}></Icon>
