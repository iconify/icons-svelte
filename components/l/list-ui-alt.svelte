<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwymv390r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwymv390r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:list-ui-alt" {...props}></Icon>
