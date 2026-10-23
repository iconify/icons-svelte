<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkh6e53fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkh6e53fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-arrow-up" {...props}></Icon>
