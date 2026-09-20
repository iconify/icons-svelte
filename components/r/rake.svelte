<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1-r8ou6u.css';
import '../../css/r/rjpmsmbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-r8ou6u"/><path class="rjpmsmbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rake" {...props}></Icon>
