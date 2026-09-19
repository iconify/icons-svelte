<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv8gugehk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv8gugehk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-show-8-group" {...props}></Icon>
