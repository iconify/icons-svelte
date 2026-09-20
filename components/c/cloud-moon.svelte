<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n77f96bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n77f96bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-moon" {...props}></Icon>
