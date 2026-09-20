<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbehteb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbehteb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:app-store-logo" {...props}></Icon>
