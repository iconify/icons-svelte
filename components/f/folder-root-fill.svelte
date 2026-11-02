<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyl8i9baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyl8i9baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-root-fill" {...props}></Icon>
