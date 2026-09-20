<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j29s27bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j29s27bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:btt" {...props}></Icon>
