<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijozgdbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijozgdbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-9-light" {...props}></Icon>
