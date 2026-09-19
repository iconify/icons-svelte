<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf_ej1bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hf_ej1bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-plus-filled" {...props}></Icon>
