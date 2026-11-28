<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cud7f3biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cud7f3biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-through-line-solid" {...props}></Icon>
