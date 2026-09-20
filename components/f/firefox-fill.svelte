<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx45nfbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wx45nfbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firefox-fill" {...props}></Icon>
