<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjv4p1bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjv4p1bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-plus" {...props}></Icon>
