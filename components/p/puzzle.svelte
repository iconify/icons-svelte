<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqf4hs3wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqf4hs3wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:puzzle" {...props}></Icon>
