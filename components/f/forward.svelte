<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpuy1fb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="tpuy1fb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:forward" {...props}></Icon>
