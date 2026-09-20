<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9-1wccab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9-1wccab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:keyboard-brightness-high" {...props}></Icon>
