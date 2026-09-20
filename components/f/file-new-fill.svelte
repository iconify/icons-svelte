<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m52v13bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m52v13bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-new-fill" {...props}></Icon>
