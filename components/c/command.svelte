<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moei0ro1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moei0ro1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:command" {...props}></Icon>
