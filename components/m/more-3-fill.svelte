<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/assb7o9lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="assb7o9lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-3-fill" {...props}></Icon>
