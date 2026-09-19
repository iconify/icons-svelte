<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcfen957l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcfen957l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:coffee-beans" {...props}></Icon>
