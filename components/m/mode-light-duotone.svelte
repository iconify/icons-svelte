<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lhlre9baf.css';
import '../../css/d/dhzjg104r.css';
import '../../css/y/yz7331f4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="lhlre9baf"/><circle class="dhzjg104r"/><path class="yz7331f4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:mode-light-duotone" {...props}></Icon>
