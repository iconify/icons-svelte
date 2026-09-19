<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj7v0vbun.css';
import '../../css/i/i28xa4bkq.css';
import '../../css/f/fli27abct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer fj7v0vbun"/><path class="duoicon-primary-layer i28xa4bkq"/><path class="duoicon-secondary-layer fli27abct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:dashboard" {...props}></Icon>
