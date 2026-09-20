<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyp_tob4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zyp_tob4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:like" {...props}></Icon>
