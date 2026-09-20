<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eka-vc8wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eka-vc8wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pig" {...props}></Icon>
