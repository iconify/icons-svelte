<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cga2esbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cga2esbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forum-delete-outline" {...props}></Icon>
