<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqm6erbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqm6erbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:netflix" {...props}></Icon>
