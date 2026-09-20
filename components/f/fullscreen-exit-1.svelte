<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x06o34gcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x06o34gcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fullscreen-exit-1" {...props}></Icon>
