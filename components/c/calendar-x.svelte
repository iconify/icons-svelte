<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cret2ebde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cret2ebde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-x" {...props}></Icon>
