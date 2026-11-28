<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py-609bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py-609bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ladder" {...props}></Icon>
