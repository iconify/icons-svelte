<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nskw_pbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nskw_pbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bioconductor" {...props}></Icon>
