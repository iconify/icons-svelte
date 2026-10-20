<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1_ej5b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1_ej5b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-check" {...props}></Icon>
