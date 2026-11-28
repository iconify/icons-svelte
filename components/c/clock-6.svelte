<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqhz7ib8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqhz7ib8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-6" {...props}></Icon>
