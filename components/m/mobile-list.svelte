<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv7e-pbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv7e-pbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mobile-list" {...props}></Icon>
