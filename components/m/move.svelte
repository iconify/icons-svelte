<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0gatlb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0gatlb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:move" {...props}></Icon>
