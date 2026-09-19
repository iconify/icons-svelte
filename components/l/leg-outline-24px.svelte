<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2njw7ubh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2njw7ubh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:leg-outline-24px" {...props}></Icon>
