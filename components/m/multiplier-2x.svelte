<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk3jipkgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk3jipkgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:multiplier-2x" {...props}></Icon>
