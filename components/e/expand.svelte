<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jix32pa3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jix32pa3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:expand" {...props}></Icon>
