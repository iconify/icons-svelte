<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scv5m7bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scv5m7bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:indifferent-ghost-solid" {...props}></Icon>
