<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o10psrw2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o10psrw2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-right-open-fill-round" {...props}></Icon>
