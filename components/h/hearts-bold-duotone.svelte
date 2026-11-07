<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0qokrk2d.css';
import '../../css/h/h4x0vob4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0qokrk2d"/><path class="h4x0vob4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hearts-bold-duotone" {...props}></Icon>
