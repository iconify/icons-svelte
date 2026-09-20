<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2mk6tb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2mk6tb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:corner-up-right" {...props}></Icon>
