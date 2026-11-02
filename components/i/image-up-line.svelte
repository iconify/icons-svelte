<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3kli2bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3kli2bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-up-line" {...props}></Icon>
