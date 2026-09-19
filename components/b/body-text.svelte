<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf7lwylwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mf7lwylwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:body-text" {...props}></Icon>
