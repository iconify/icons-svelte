<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhqua-lqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhqua-lqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pin-alt-2-line" {...props}></Icon>
