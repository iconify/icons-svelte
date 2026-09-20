<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c89x4jb8t.css';
import '../../css/l/l2c2myl2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c89x4jb8t"/><path class="l2c2myl2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:car-engine-11-bold" {...props}></Icon>
