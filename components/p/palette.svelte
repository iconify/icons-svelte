<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6cki_2wy.css';
import '../../css/x/x2dxx-bdb.css';
import '../../css/z/zeckvdf7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer p6cki_2wy"/><path class="duoicon-primary-layer x2dxx-bdb"/><path class="duoicon-secondary-layer zeckvdf7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:palette" {...props}></Icon>
