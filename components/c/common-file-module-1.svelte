<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag3k93sbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag3k93sbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-module-1" {...props}></Icon>
