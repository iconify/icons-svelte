<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apqxuwf4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apqxuwf4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-appearance" {...props}></Icon>
