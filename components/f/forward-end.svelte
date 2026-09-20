<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibx1aab1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibx1aab1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:forward-end" {...props}></Icon>
