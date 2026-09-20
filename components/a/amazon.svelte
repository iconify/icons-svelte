<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a326w2bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a326w2bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:amazon" {...props}></Icon>
