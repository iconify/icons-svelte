<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krf3bhb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krf3bhb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-top" {...props}></Icon>
