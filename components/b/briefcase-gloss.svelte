<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1v7bsd3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1v7bsd3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:briefcase-gloss" {...props}></Icon>
