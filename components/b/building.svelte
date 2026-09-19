<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/texanzbed.css';
import '../../css/f/fmf3k-28m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer texanzbed"/><path class="duoicon-primary-layer fmf3k-28m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:building" {...props}></Icon>
