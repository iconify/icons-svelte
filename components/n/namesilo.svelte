<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_-yizo_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_-yizo_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:namesilo" {...props}></Icon>
