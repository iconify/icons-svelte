<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b59g63b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b59g63b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:esoteric-software" {...props}></Icon>
