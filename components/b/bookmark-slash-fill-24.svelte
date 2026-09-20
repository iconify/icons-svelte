<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq5os2voj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq5os2voj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark-slash-fill-24" {...props}></Icon>
