<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms01scbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms01scbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-brain-solid" {...props}></Icon>
