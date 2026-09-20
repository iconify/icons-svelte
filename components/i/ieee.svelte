<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyeitla7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyeitla7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ieee" {...props}></Icon>
