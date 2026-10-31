<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkv3n0bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkv3n0bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:component-instance-round" {...props}></Icon>
