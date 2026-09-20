<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojj3akbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojj3akbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:plus-minus" {...props}></Icon>
