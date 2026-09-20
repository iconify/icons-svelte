<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfgdjs2-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgdjs2-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-summarize-line" {...props}></Icon>
