<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rotxfmb0f.css';
import '../../css/e/ekbk75bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rotxfmb0f"/><path class="ekbk75bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:power-filled" {...props}></Icon>
