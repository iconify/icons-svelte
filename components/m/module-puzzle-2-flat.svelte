<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7zhdfbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e7zhdfbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:module-puzzle-2-flat" {...props}></Icon>
