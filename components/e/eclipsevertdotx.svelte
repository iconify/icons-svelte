<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-f6te6sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-f6te6sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:eclipsevertdotx" {...props}></Icon>
