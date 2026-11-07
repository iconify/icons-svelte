<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4lfqkpls.css';
import '../../css/p/pzmtr-buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4lfqkpls"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-up-outline" {...props}></Icon>
