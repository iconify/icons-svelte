<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haija_bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="haija_bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-left-square-fill" {...props}></Icon>
