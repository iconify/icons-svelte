<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2c57gbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2c57gbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:line-app-fill" {...props}></Icon>
