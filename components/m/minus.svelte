<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td2hy69fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td2hy69fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:minus" {...props}></Icon>
