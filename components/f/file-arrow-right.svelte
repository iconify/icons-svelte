<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o23fqybmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o23fqybmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-arrow-right" {...props}></Icon>
