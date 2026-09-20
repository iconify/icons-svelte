<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i22an_d-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i22an_d-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:caret-up" {...props}></Icon>
