<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0tz0buop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="j0tz0buop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:factory" {...props}></Icon>
