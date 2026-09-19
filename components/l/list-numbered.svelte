<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9jy5tr7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9jy5tr7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:list-numbered" {...props}></Icon>
