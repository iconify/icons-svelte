<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm3i78bcl.css';
import '../../css/d/d0bz8sb9m.css';
import '../../css/z/zzlmo8aoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm3i78bcl"/><path class="d0bz8sb9m"/><path class="zzlmo8aoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:confused" {...props}></Icon>
