<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-elg5b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-elg5b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-minus" {...props}></Icon>
