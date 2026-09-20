<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj3_hyblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj3_hyblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-scan-fill" {...props}></Icon>
