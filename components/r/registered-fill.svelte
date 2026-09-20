<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o21vrx0-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o21vrx0-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:registered-fill" {...props}></Icon>
