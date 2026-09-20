<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/far40sbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="far40sbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:backpack-f" {...props}></Icon>
