<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdgfu3b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdgfu3b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drizzle-fill" {...props}></Icon>
