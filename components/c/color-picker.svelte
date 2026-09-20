<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvwij9-lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mvwij9-lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:color-picker" {...props}></Icon>
