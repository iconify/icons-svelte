<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kucghu1pp.css';
import '../../css/v/v3bumgb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kucghu1pp"/><path class="v3bumgb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:real-debrid-dark" {...props}></Icon>
