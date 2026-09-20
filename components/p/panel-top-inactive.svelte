<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt9b5egoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt9b5egoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-top-inactive" {...props}></Icon>
