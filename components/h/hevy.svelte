<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx22tj45e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx22tj45e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hevy" {...props}></Icon>
