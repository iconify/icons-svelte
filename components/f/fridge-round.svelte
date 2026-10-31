<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywvmuh6-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywvmuh6-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fridge-round" {...props}></Icon>
