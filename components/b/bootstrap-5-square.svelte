<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3-4llncc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3-4llncc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bootstrap-5-square" {...props}></Icon>
