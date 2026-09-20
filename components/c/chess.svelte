<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsyg-3lal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsyg-3lal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chess" {...props}></Icon>
