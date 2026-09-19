<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6jgkpjrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6jgkpjrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-lock" {...props}></Icon>
