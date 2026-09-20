<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhvz2l3_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhvz2l3_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:console" {...props}></Icon>
