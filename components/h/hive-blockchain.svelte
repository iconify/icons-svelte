<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djuy7yu_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djuy7yu_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hive-blockchain" {...props}></Icon>
