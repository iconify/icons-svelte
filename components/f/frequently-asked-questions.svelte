<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmesgm11x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmesgm11x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:frequently-asked-questions" {...props}></Icon>
