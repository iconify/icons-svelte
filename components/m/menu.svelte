<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm6fy4buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm6fy4buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:menu" {...props}></Icon>
