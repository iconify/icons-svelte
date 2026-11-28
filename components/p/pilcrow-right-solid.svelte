<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxg-2ccoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxg-2ccoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pilcrow-right-solid" {...props}></Icon>
