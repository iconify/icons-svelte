<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhkqh8bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhkqh8bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-distribute-center" {...props}></Icon>
