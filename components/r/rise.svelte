<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tok7ryb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tok7ryb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rise" {...props}></Icon>
