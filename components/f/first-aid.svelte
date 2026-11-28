<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee-sbeb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee-sbeb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:first-aid" {...props}></Icon>
