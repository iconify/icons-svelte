<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvnnzl8ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vvnnzl8ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bicycle-16-solid" {...props}></Icon>
