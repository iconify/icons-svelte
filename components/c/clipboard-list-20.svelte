<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg-os2b_i.css';
import '../../css/n/n3ia57pse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xg-os2b_i"/><path class="n3ia57pse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-list-20" {...props}></Icon>
