<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqghtebog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqghtebog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:eye-off-fill" {...props}></Icon>
