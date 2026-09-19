<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_j3_zqkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_j3_zqkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-check" {...props}></Icon>
