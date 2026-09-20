<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe9q2s79t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe9q2s79t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-delete" {...props}></Icon>
