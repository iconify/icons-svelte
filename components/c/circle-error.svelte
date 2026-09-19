<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn7gsfbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn7gsfbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:circle-error" {...props}></Icon>
