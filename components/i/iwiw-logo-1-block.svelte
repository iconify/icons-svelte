<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al6eot8sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="al6eot8sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iwiw-logo-1-block" {...props}></Icon>
