<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rslkvhswy.css';
import '../../css/u/ug_dfdboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rslkvhswy"/><path class="ug_dfdboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-alt-circle-left" {...props}></Icon>
