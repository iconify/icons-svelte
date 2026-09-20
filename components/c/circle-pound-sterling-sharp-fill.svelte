<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j60a46bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j60a46bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-pound-sterling-sharp-fill" {...props}></Icon>
