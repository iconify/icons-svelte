<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr0t56j8f.css';
import '../../css/v/vqxkeugkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sr0t56j8f"/><path class="vqxkeugkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-48-bold" {...props}></Icon>
