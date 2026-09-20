<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj6zkua8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj6zkua8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pin-alt-2-fill" {...props}></Icon>
