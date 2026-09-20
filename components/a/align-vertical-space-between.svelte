<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/i2h9tmbip.css';
import '../../css/b/bswdohf5f.css';
import '../../css/d/dgdhsgi6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="i2h9tmbip"/><rect class="bswdohf5f"/><path class="dgdhsgi6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:align-vertical-space-between" {...props}></Icon>
