<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/int9g14to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="int9g14to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:envelope-open" {...props}></Icon>
