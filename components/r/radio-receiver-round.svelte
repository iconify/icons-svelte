<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghomjxdge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghomjxdge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radio-receiver-round" {...props}></Icon>
