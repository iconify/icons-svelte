<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpj-7ybes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpj-7ybes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage-hexagon" {...props}></Icon>
