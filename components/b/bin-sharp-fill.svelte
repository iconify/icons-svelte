<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inyb3balg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inyb3balg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bin-sharp-fill" {...props}></Icon>
