<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j14of8izp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j14of8izp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:expand-solid" {...props}></Icon>
