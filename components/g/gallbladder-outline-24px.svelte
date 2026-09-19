<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmb74bbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmb74bbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gallbladder-outline-24px" {...props}></Icon>
