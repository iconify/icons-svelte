<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbb06tbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbb06tbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hail-line" {...props}></Icon>
