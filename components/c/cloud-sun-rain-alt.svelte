<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-0q-6bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-0q-6bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-sun-rain-alt" {...props}></Icon>
