<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du2t3dkjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du2t3dkjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amul" {...props}></Icon>
