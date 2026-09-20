<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ld-7b2f.css';
import '../../css/b/b1u7f-d_l.css';
import '../../css/q/qw5i-xb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b4ld-7b2f"/><path class="b1u7f-d_l"/><path class="qw5i-xb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-satellite" {...props}></Icon>
