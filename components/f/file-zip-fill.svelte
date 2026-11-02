<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q26x31bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q26x31bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-zip-fill" {...props}></Icon>
