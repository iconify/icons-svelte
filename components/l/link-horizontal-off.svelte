<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcmm31bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcmm31bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:link-horizontal-off" {...props}></Icon>
