<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu0ax1bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu0ax1bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-waves" {...props}></Icon>
