<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u62_j_zii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u62_j_zii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-chevrons-up-down" {...props}></Icon>
