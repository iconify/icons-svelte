<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1h9t678t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1h9t678t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-alt-solid" {...props}></Icon>
