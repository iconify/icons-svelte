<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6hnyjb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v6hnyjb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-center-fill-12" {...props}></Icon>
