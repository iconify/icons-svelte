<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tedctybex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tedctybex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:boy-sharp" {...props}></Icon>
