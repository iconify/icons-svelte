<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfu6rac0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfu6rac0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-medium-fill-round" {...props}></Icon>
