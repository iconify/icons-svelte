<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3rx1sb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3rx1sb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:book-medical" {...props}></Icon>
