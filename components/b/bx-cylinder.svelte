<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piu1gj3kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piu1gj3kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cylinder" {...props}></Icon>
