<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys997ib-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys997ib-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-align-center" {...props}></Icon>
