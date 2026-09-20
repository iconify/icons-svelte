<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iosqv_6xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iosqv_6xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-right-close-solid" {...props}></Icon>
