<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohm9ldbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohm9ldbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-down-sharp-fill" {...props}></Icon>
