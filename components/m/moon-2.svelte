<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6-p3cb7a.css';
import '../../css/s/sxs8wrbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6-p3cb7a duoicon-primary-layer"/><path class="duoicon-secondary-layer sxs8wrbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:moon-2" {...props}></Icon>
