<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egmvb8bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egmvb8bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reminder" {...props}></Icon>
