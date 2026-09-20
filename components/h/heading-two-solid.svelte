<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acyf46khq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acyf46khq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-two-solid" {...props}></Icon>
