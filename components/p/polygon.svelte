<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auooq3bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auooq3bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:polygon" {...props}></Icon>
