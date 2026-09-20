<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtvukff6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtvukff6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opslevel" {...props}></Icon>
