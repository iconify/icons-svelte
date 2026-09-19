<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn045t_wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn045t_wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:plus-small" {...props}></Icon>
