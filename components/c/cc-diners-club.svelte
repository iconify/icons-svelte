<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vym9ewb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vym9ewb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-diners-club" {...props}></Icon>
