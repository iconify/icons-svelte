<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etpu_euix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etpu_euix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bell" {...props}></Icon>
