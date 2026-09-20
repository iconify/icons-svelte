<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ycasbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ycasbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-minus" {...props}></Icon>
