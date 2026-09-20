<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyj7c0ewx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyj7c0ewx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:align-right" {...props}></Icon>
