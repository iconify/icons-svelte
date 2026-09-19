<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thh54cc_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="thh54cc_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:insert-page" {...props}></Icon>
