<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbwj8s5ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbwj8s5ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:alarm-smoke" {...props}></Icon>
