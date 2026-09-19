<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f949bccnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f949bccnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glass-door3-open" {...props}></Icon>
