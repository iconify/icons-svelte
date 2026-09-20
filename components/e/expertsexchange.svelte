<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_yzqlbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_yzqlbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:expertsexchange" {...props}></Icon>
