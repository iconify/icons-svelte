<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-aybzt8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-aybzt8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:expand-solid" {...props}></Icon>
