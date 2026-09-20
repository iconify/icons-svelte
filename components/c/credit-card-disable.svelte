<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-r-f4b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-r-f4b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:credit-card-disable" {...props}></Icon>
