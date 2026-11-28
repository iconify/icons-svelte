<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zflwx6kpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zflwx6kpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mask" {...props}></Icon>
