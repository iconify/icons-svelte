<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk09nrg1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk09nrg1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-s-fill" {...props}></Icon>
