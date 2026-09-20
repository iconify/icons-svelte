<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o72e3cdbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o72e3cdbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:baggage" {...props}></Icon>
