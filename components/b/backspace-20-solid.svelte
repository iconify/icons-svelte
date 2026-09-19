<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epm3pib-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="epm3pib-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:backspace-20-solid" {...props}></Icon>
