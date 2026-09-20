<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ropp-6rfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ropp-6rfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aftership" {...props}></Icon>
