<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk92eoj1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk92eoj1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:radial-rays-solid" {...props}></Icon>
