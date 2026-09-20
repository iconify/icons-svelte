<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjt0m6brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjt0m6brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crown5-filled" {...props}></Icon>
