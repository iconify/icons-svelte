<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kufnkgbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kufnkgbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cancel-box-multiple" {...props}></Icon>
