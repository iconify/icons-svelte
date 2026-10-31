<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1om5ryxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1om5ryxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:info-duotone-round" {...props}></Icon>
