<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkg_txz7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkg_txz7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:robot-happy-fill" {...props}></Icon>
