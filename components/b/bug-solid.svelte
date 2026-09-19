<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrdugdbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrdugdbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bug-solid" {...props}></Icon>
