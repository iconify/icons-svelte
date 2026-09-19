<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs9_k7rdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs9_k7rdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-add-thin" {...props}></Icon>
