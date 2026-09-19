<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9lfmybtd.css';
import '../../css/f/fypx88b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9lfmybtd"/><path class="fypx88b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-chip" {...props}></Icon>
