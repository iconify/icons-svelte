<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/een1a4tir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="een1a4tir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chalkboard-user-outline" {...props}></Icon>
