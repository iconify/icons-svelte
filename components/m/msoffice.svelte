<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d49ee6kaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d49ee6kaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:msoffice" {...props}></Icon>
