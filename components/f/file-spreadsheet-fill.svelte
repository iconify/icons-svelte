<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvw4nff7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zvw4nff7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-spreadsheet-fill" {...props}></Icon>
