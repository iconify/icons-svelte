<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkw6vqu9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkw6vqu9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:calendar" {...props}></Icon>
