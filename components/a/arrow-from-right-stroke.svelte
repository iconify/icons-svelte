<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euem3vl2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euem3vl2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-from-right-stroke" {...props}></Icon>
