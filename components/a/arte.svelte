<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghg5mfmuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghg5mfmuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arte" {...props}></Icon>
