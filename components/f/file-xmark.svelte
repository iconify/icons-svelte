<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbe3tm0cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qbe3tm0cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-xmark" {...props}></Icon>
