<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x200m4bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x200m4bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-right-expressive" {...props}></Icon>
