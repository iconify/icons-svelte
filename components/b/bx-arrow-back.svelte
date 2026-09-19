<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxqr7tbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxqr7tbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-arrow-back" {...props}></Icon>
