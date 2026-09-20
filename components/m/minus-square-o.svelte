<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er-mwtbxn.css';
import '../../css/c/cflr1ab0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="er-mwtbxn"/><path class="cflr1ab0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:minus-square-o" {...props}></Icon>
