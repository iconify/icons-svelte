<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig2zuj_ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig2zuj_ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ai-fill" {...props}></Icon>
