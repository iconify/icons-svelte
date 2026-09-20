<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v106kq0eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v106kq0eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:menu" {...props}></Icon>
