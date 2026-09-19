<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvx9jwbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvx9jwbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-up-fill" {...props}></Icon>
