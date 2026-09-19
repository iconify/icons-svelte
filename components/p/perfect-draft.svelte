<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auo_0gbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auo_0gbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:perfect-draft" {...props}></Icon>
