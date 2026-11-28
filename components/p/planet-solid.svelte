<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njo06tbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njo06tbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:planet-solid" {...props}></Icon>
