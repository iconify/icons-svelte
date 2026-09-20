<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5yoz6nou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5yoz6nou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-student" {...props}></Icon>
