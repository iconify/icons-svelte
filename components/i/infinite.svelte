<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia9t81bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia9t81bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:infinite" {...props}></Icon>
