<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouz5ddbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouz5ddbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bell-solid" {...props}></Icon>
