<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vscd-0bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vscd-0bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-narrow-wide-sharp-fill" {...props}></Icon>
