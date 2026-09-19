<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp7nxbb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp7nxbb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-right-solid" {...props}></Icon>
