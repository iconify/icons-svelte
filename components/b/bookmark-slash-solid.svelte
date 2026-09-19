<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2kge9byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2kge9byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-slash-solid" {...props}></Icon>
