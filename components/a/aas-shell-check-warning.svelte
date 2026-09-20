<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h53zl9biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h53zl9biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-check-warning" {...props}></Icon>
