<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbdd10buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbdd10buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:mountains" {...props}></Icon>
