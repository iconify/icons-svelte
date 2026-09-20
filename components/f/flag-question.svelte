<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivg_vn4vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivg_vn4vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-question" {...props}></Icon>
