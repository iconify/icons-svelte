<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvzoyhbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvzoyhbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hedgedoc" {...props}></Icon>
