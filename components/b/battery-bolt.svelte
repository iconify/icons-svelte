<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrody-bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrody-bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:battery-bolt" {...props}></Icon>
