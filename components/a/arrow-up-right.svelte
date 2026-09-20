<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_eh4wkjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_eh4wkjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:arrow-up-right" {...props}></Icon>
