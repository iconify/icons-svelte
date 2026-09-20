<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4cz4exyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4cz4exyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:clion" {...props}></Icon>
