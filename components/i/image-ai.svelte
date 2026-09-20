<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf46vybxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf46vybxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:image-ai" {...props}></Icon>
