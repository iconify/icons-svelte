<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw7-8ydfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw7-8ydfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-w-circle-solid" {...props}></Icon>
