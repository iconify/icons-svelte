<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0d8qi36j.css';
import '../../css/j/jej9w9b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0d8qi36j"/><path class="jej9w9b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fish-line" {...props}></Icon>
