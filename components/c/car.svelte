<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwxp4tvzv.css';
import '../../css/d/dyto25hnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer nwxp4tvzv"/><path class="duoicon-primary-layer dyto25hnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:car" {...props}></Icon>
