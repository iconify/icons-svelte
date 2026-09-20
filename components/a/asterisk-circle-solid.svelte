<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcx275bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcx275bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-circle-solid" {...props}></Icon>
