<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6dqfo8re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256,"top":-6};
const content = `<path class="d6dqfo8re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:redux" {...props}></Icon>
