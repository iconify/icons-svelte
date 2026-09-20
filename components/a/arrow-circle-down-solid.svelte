<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9cm65b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9cm65b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-circle-down-solid" {...props}></Icon>
