<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p766x0cdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p766x0cdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:prostate-outline-24px" {...props}></Icon>
