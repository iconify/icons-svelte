<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeh33x6-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oeh33x6-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:maximize" {...props}></Icon>
