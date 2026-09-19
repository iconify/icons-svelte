<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4pbix25t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="h4pbix25t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:edit-compact" {...props}></Icon>
