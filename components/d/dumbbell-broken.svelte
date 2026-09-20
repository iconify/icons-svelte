<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pueh8h4nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pueh8h4nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-broken" {...props}></Icon>
