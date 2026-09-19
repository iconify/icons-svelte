<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uck3k8wiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uck3k8wiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-underline" {...props}></Icon>
