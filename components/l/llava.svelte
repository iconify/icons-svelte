<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd7x9qb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd7x9qb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:llava" {...props}></Icon>
