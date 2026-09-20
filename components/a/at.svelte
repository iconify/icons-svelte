<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxx4uub5u.css';
import '../../css/m/m7s1g-b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxx4uub5u"/><path class="m7s1g-b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:at" {...props}></Icon>
