<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-qxs6lvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-qxs6lvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cabinet-04" {...props}></Icon>
