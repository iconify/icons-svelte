<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob991ac-v.css';
import '../../css/l/lbnegcbec.css';
import '../../css/v/vneknnfuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob991ac-v"/><path class="lbnegcbec"/><path class="vneknnfuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:earth-refresh-bold" {...props}></Icon>
