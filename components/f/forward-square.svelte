<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n76b9-wlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="n76b9-wlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:forward-square" {...props}></Icon>
