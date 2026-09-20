<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejqlnfw-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ejqlnfw-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:cloud-pod" {...props}></Icon>
