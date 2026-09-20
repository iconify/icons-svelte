<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeap7yb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeap7yb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-left-solid" {...props}></Icon>
