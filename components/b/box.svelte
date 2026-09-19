<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_iv7psnh.css';
import '../../css/r/rlhcac1kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer y_iv7psnh"/><path class="duoicon-primary-layer rlhcac1kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:box" {...props}></Icon>
