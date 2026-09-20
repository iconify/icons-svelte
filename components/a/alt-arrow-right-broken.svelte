<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz-yv_bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz-yv_bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-right-broken" {...props}></Icon>
