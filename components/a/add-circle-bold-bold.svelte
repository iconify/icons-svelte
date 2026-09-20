<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlb2rkunv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlb2rkunv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:add-circle-bold-bold" {...props}></Icon>
