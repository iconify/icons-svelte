<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4y7hyhux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4y7hyhux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-symlink-fill" {...props}></Icon>
