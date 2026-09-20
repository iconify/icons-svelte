<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgv4vo-wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgv4vo-wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:datagrip" {...props}></Icon>
