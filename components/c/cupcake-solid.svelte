<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_2k7vlvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_2k7vlvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cupcake-solid" {...props}></Icon>
