<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t31vdhbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t31vdhbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:podcast-addict" {...props}></Icon>
