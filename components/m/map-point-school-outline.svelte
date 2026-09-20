<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufm-cjv9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufm-cjv9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-school-outline" {...props}></Icon>
