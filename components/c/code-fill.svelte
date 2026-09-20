<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hczt0qb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hczt0qb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:code-fill" {...props}></Icon>
