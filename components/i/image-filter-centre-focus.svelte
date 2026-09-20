<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivylbb__r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivylbb__r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-centre-focus" {...props}></Icon>
