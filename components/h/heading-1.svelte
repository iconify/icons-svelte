<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgu6i8a0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgu6i8a0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:heading-1" {...props}></Icon>
