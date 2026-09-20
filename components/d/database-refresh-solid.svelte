<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jod_b1bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jod_b1bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-refresh-solid" {...props}></Icon>
