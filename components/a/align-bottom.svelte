<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4y6mmu1p.css';
import '../../css/r/rc6lwuj7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer r4y6mmu1p"/><path class="duoicon-primary-layer rc6lwuj7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:align-bottom" {...props}></Icon>
