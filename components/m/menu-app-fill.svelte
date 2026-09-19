<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol_k1ab-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ol_k1ab-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:menu-app-fill" {...props}></Icon>
