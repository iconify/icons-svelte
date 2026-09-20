<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa1odgbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1odgbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:external-link" {...props}></Icon>
