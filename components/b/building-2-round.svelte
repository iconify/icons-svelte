<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o80jv3eoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o80jv3eoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-2-round" {...props}></Icon>
