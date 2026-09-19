<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erfmhctcc.css';
import '../../css/b/b-t5aibbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer erfmhctcc"/><path class="b-t5aibbb duoicon-secondary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:location" {...props}></Icon>
