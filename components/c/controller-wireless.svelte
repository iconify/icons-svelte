<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3c357bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3c357bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:controller-wireless" {...props}></Icon>
