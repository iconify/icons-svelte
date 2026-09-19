<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghv_czu6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghv_czu6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-to-right-stroke" {...props}></Icon>
