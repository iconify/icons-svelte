<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n11x2ztin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n11x2ztin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:external-link" {...props}></Icon>
