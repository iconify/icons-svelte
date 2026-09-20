<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4hp8l9sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4hp8l9sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:comment" {...props}></Icon>
