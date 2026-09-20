<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oay60c9mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oay60c9mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cart" {...props}></Icon>
