<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch04xou5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch04xou5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-add" {...props}></Icon>
