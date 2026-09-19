<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-_jerb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-_jerb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:chevron-down-outline" {...props}></Icon>
