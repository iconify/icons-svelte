<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbq5kebal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbq5kebal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rotate-to-vertical-fill" {...props}></Icon>
