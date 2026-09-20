<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-6ptdbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-6ptdbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-up-sharp-fill" {...props}></Icon>
