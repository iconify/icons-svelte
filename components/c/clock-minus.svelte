<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6nz7yjgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6nz7yjgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-minus" {...props}></Icon>
