<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijspo9nkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijspo9nkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cancer-fill" {...props}></Icon>
