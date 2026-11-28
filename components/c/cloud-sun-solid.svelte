<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdb1cx7ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdb1cx7ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-sun-solid" {...props}></Icon>
