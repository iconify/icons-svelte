<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8qs2k-uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8qs2k-uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-world" {...props}></Icon>
