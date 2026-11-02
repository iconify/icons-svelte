<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwe_sbcat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwe_sbcat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-clock-line" {...props}></Icon>
