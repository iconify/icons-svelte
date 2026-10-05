<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-u4vjbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-u4vjbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:more-vertical" {...props}></Icon>
