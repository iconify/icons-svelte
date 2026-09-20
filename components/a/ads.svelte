<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yugx7jbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yugx7jbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ads" {...props}></Icon>
