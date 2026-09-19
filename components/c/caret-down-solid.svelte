<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjh52cczs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xjh52cczs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caret-down-solid" {...props}></Icon>
