<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agc4itbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agc4itbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:nurse-line" {...props}></Icon>
