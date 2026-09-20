<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2vhnvzam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2vhnvzam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down2-filled" {...props}></Icon>
