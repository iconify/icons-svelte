<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne-zux08d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne-zux08d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:exclude" {...props}></Icon>
