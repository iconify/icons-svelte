<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df8xwmbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df8xwmbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:add-plus-square" {...props}></Icon>
