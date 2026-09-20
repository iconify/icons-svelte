<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2ou5m2vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2ou5m2vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-10-box" {...props}></Icon>
