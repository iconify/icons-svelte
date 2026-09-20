<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5e054bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5e054bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bhat" {...props}></Icon>
