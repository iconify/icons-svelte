<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebw6zj4kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebw6zj4kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hanger-check" {...props}></Icon>
