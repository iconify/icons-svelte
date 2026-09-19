<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue4blbbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="ue4blbbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:night-alt-lightning" {...props}></Icon>
