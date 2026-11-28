<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc68r29ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc68r29ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:panel-bottom-solid" {...props}></Icon>
