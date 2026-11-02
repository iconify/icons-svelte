<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8q-x2bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8q-x2bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-open-dot-fill" {...props}></Icon>
