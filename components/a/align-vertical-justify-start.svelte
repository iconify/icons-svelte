<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yasjebbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yasjebbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-vertical-justify-start" {...props}></Icon>
