<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s04f8kb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s04f8kb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:desk-lamp" {...props}></Icon>
