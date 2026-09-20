<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc4v6obfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc4v6obfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:film" {...props}></Icon>
