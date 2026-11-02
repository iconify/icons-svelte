<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwb95wbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwb95wbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-3-fill" {...props}></Icon>
