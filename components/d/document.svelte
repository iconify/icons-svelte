<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccd6l0zmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccd6l0zmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:document" {...props}></Icon>
