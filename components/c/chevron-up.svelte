<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9to7_n9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9to7_n9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up" {...props}></Icon>
