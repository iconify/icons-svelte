<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqc0s_98y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="iqc0s_98y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:plane" {...props}></Icon>
