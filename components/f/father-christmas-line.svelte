<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui8ehd76t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui8ehd76t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:father-christmas-line" {...props}></Icon>
