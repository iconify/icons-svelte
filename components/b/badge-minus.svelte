<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c399ppbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c399ppbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-minus" {...props}></Icon>
