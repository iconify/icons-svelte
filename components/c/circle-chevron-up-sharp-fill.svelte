<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omd6vzz8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omd6vzz8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevron-up-sharp-fill" {...props}></Icon>
