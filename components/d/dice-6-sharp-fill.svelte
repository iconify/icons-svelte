<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0zocwx_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0zocwx_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-6-sharp-fill" {...props}></Icon>
