<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb280mnli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb280mnli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:play-solid" {...props}></Icon>
