<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tylz4_gen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tylz4_gen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:martini" {...props}></Icon>
