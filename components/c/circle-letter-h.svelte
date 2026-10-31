<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyp7zparo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyp7zparo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-letter-h" {...props}></Icon>
