<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyc9jsn5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyc9jsn5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:divide" {...props}></Icon>
