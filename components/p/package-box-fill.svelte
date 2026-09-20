<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxc_ccc7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxc_ccc7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:package-box-fill" {...props}></Icon>
