<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3op2qbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3op2qbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:deepfake-technology-2-solid" {...props}></Icon>
