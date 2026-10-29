<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks9q9jbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks9q9jbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gauge-solid" {...props}></Icon>
