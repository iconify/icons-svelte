<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/augn52bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="augn52bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-sharp-fill" {...props}></Icon>
