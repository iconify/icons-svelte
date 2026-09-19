<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijh_5fbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijh_5fbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:map-outline" {...props}></Icon>
