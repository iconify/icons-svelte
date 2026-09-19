<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c208yhbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c208yhbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:jar-wheat-outline" {...props}></Icon>
