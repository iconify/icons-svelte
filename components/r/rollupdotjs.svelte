<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skbujj1ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skbujj1ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rollupdotjs" {...props}></Icon>
