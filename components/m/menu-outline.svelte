<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdq37lsuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jdq37lsuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:menu-outline" {...props}></Icon>
