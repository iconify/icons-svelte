<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh5f5isdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh5f5isdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-rate-open-variant" {...props}></Icon>
