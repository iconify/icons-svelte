<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxyj62m0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jxyj62m0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:fast-forward-btn-fill" {...props}></Icon>
