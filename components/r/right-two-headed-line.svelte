<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4o2u6vyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4o2u6vyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:right-two-headed-line" {...props}></Icon>
