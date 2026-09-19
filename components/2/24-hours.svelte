<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvjt2gvvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvjt2gvvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:24-hours" {...props}></Icon>
