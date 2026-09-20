<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd-3rgbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gd-3rgbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-wave" {...props}></Icon>
