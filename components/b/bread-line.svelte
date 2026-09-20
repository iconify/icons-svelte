<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmtm7pz0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmtm7pz0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bread-line" {...props}></Icon>
