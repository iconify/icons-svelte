<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdgva3ibz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdgva3ibz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:equalizer" {...props}></Icon>
