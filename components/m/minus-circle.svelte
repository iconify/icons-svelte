<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzq0o3a5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzq0o3a5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:minus-circle" {...props}></Icon>
