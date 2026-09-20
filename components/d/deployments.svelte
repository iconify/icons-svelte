<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxyw-3zpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cxyw-3zpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:deployments" {...props}></Icon>
