<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_-_wl61g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-_wl61g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pen-filled" {...props}></Icon>
