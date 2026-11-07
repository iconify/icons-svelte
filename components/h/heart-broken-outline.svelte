<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuun1mbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cuun1mbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-broken-outline" {...props}></Icon>
