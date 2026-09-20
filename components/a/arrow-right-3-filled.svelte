<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd4zl3h1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd4zl3h1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-3-filled" {...props}></Icon>
