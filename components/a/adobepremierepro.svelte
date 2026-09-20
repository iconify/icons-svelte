<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0hgu_24w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0hgu_24w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adobepremierepro" {...props}></Icon>
