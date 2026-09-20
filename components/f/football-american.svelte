<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8r7hnbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8r7hnbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:football-american" {...props}></Icon>
