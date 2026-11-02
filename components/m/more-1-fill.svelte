<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc4vskb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc4vskb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-1-fill" {...props}></Icon>
