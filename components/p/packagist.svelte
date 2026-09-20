<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahf0zc3zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahf0zc3zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:packagist" {...props}></Icon>
