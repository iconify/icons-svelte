<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwaaxn44y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwaaxn44y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-monero" {...props}></Icon>
