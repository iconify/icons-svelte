<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzai23bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzai23bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:minus" {...props}></Icon>
