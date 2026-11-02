<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt0n_4ynm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt0n_4ynm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-edit-fill" {...props}></Icon>
