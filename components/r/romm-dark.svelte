<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v12ih4bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v12ih4bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:romm-dark" {...props}></Icon>
