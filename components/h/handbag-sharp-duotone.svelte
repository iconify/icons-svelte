<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjdnx9y7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjdnx9y7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:handbag-sharp-duotone" {...props}></Icon>
