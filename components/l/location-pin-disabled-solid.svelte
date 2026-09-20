<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3t0lctow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k3t0lctow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:location-pin-disabled-solid" {...props}></Icon>
