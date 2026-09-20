<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdz8q2beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":250,"height":250};
const content = `<path clip-rule="evenodd" class="gdz8q2beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:plop" {...props}></Icon>
