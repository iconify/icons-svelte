<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fapcdg5-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fapcdg5-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:calendar" {...props}></Icon>
