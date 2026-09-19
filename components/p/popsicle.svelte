<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c38x5m7rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c38x5m7rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:popsicle" {...props}></Icon>
