<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzwmi2b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzwmi2b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:list-box" {...props}></Icon>
