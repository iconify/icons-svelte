<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq2j_5g3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":470,"height":512};
const content = `<path class="hq2j_5g3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cnab" {...props}></Icon>
