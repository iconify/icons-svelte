<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf8g-d54i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf8g-d54i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:numpy" {...props}></Icon>
