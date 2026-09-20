<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa6pgeb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pa6pgeb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart-pulse2" {...props}></Icon>
