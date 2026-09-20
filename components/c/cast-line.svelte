<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3meejbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3meejbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cast-line" {...props}></Icon>
