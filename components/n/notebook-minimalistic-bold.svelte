<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwqzobcjb.css';
import '../../css/i/ildxxvqdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwqzobcjb"/><path class="ildxxvqdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-minimalistic-bold" {...props}></Icon>
