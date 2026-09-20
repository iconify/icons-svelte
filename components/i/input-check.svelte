<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvj_lcboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvj_lcboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:input-check" {...props}></Icon>
