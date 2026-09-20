<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn--p_9ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn--p_9ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bluetooth-fill" {...props}></Icon>
