<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5rfv4tlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5rfv4tlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-bottom-inactive-solid" {...props}></Icon>
