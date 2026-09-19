<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g35llpa4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":24};
const content = `<path class="g35llpa4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:lightbulb" {...props}></Icon>
