<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8735r-je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8735r-je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:coffee-sharp" {...props}></Icon>
