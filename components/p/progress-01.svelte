<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_c5_kbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="a_c5_kbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:progress-01" {...props}></Icon>
