<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc7n59pdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc7n59pdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-x-sharp" {...props}></Icon>
