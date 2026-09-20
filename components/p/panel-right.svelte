<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzm838bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzm838bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:panel-right" {...props}></Icon>
