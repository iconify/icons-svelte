<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fic-uk24y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fic-uk24y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout" {...props}></Icon>
