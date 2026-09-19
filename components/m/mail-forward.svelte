<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itkqu9bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1600};
const content = `<path class="itkqu9bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mail-forward" {...props}></Icon>
