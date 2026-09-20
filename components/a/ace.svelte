<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izu0r0bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izu0r0bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ace" {...props}></Icon>
