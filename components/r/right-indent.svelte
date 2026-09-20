<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1mvc2rbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1mvc2rbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:right-indent" {...props}></Icon>
