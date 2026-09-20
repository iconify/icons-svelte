<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4cbddb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4cbddb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:percentage-circle-filled" {...props}></Icon>
