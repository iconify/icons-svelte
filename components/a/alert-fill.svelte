<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brq9xm1sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brq9xm1sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-fill" {...props}></Icon>
