<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyneov3ti.css';
import '../../css/j/jiglepbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer iyneov3ti"/><path class="duoicon-primary-layer jiglepbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:clock" {...props}></Icon>
