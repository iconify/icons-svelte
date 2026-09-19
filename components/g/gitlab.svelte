<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqvzkclwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqvzkclwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:gitlab" {...props}></Icon>
