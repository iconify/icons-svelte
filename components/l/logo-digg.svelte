<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa35v-cta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oa35v-cta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-digg" {...props}></Icon>
