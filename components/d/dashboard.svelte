<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8m6mibuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8m6mibuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dashboard" {...props}></Icon>
