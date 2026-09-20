<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0834k1ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0834k1ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-narrow-wide-sharp" {...props}></Icon>
