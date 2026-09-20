<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypeyqq57o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypeyqq57o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:menu-expand-left-line" {...props}></Icon>
