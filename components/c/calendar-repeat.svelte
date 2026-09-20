<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm27_s1id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm27_s1id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-repeat" {...props}></Icon>
