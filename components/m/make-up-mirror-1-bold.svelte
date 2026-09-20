<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-bzdbb5h.css';
import '../../css/i/ij-ynac5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-bzdbb5h"/><path class="ij-ynac5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:make-up-mirror-1-bold" {...props}></Icon>
