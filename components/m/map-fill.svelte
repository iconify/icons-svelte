<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzko38s9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzko38s9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-fill" {...props}></Icon>
