<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjyx7za2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjyx7za2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:angry-fill" {...props}></Icon>
