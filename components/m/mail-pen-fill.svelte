<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb4anud9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb4anud9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-pen-fill" {...props}></Icon>
