<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiob6verm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uiob6verm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:grid-fill" {...props}></Icon>
