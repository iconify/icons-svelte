<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vupesl-hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vupesl-hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-up-double-bold" {...props}></Icon>
