<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4xxgybar.css';
import '../../css/h/hujkt7abw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4xxgybar"/><path class="hujkt7abw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-upload-filled" {...props}></Icon>
