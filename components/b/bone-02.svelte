<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbt2w33fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbt2w33fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bone-02" {...props}></Icon>
