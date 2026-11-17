<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk49mkgwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk49mkgwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bot-x" {...props}></Icon>
