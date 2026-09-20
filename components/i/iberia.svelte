<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8ndb9t_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8ndb9t_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:iberia" {...props}></Icon>
