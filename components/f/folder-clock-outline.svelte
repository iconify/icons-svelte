<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7p-8cptj.css';
import '../../css/u/uu8xqrboc.css';
import '../../css/p/pzmtr-buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7p-8cptj"/><path clip-rule="evenodd" class="uu8xqrboc"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-clock-outline" {...props}></Icon>
