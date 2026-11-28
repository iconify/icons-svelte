<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_t2o4b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_t2o4b7l primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-left-duotone" {...props}></Icon>
