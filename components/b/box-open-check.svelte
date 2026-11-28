<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xae-8gbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xae-8gbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:box-open-check" {...props}></Icon>
