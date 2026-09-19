<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogqybibiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogqybibiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cake" {...props}></Icon>
