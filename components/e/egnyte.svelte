<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9jijnt_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9jijnt_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:egnyte" {...props}></Icon>
