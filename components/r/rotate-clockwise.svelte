<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufp82bbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufp82bbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rotate-clockwise" {...props}></Icon>
