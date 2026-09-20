<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8bi2496u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8bi2496u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-left-inactive" {...props}></Icon>
