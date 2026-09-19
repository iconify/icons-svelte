<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se8oa-w5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se8oa-w5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chalkboard-outline" {...props}></Icon>
