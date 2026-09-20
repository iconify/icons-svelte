<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4xnnr36c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4xnnr36c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-double-fill" {...props}></Icon>
