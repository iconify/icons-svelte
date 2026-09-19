<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekk48rbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekk48rbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:arrow-right" {...props}></Icon>
