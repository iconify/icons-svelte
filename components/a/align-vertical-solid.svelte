<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwmr-xfuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwmr-xfuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-vertical-solid" {...props}></Icon>
