<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm33wjbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm33wjbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:clock" {...props}></Icon>
