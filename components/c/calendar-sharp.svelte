<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-mj0wift.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-mj0wift"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-sharp" {...props}></Icon>
