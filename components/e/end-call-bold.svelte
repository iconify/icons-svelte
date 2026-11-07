<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9_2j3bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9_2j3bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-bold" {...props}></Icon>
