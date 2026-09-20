<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my_i5-smp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my_i5-smp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:italics" {...props}></Icon>
