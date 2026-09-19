<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h71lwbcrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="h71lwbcrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bus" {...props}></Icon>
