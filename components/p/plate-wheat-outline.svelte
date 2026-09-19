<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8s2ht79g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8s2ht79g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:plate-wheat-outline" {...props}></Icon>
