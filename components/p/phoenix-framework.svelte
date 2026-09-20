<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npqxpew6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npqxpew6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:phoenix-framework" {...props}></Icon>
