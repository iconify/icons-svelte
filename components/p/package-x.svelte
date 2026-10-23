<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6tfk08ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6tfk08ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:package-x" {...props}></Icon>
