<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u19voll5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u19voll5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:info-circle-solid" {...props}></Icon>
