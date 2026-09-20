<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih0jbwzum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0jbwzum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:direction" {...props}></Icon>
