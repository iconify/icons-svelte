<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu17u970l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu17u970l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lollipop-fill" {...props}></Icon>
