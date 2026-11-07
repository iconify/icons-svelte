<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hexx2yb1s.css';
import '../../css/e/epahso09d.css';
import '../../css/g/g4e643m4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hexx2yb1s"/><path class="epahso09d"/><path clip-rule="evenodd" class="g4e643m4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:info-square-outline" {...props}></Icon>
