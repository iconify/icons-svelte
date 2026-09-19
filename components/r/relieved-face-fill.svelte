<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i37p3-q5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i37p3-q5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:relieved-face-fill" {...props}></Icon>
