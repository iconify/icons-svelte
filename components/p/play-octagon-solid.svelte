<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7c27bb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7c27bb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:play-octagon-solid" {...props}></Icon>
