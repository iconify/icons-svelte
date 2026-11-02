<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7q9k5bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7q9k5bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:facebook-line" {...props}></Icon>
