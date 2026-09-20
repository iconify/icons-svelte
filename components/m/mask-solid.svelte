<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfka-bcwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfka-bcwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mask-solid" {...props}></Icon>
