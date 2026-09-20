<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ossksxb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ossksxb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-column-sharp" {...props}></Icon>
