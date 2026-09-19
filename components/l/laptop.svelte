<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpo11j3ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="cpo11j3ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:laptop" {...props}></Icon>
