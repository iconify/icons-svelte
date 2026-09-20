<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pua9qbbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pua9qbbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:dimond-fill" {...props}></Icon>
