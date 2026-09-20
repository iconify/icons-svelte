<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcj88du6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcj88du6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-cog-outline" {...props}></Icon>
