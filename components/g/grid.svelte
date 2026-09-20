<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2wijgb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e2wijgb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:grid" {...props}></Icon>
