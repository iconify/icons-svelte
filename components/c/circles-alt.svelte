<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-isj0bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-isj0bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circles-alt" {...props}></Icon>
