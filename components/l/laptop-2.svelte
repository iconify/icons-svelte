<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jav-cm73x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jav-cm73x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:laptop-2" {...props}></Icon>
