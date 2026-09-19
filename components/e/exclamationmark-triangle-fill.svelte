<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i29s6sbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i29s6sbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:exclamationmark-triangle-fill" {...props}></Icon>
