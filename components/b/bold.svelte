<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi2j6qb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="yi2j6qb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:bold" {...props}></Icon>
