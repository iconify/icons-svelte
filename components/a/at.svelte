<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rom2-fbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rom2-fbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:at" {...props}></Icon>
