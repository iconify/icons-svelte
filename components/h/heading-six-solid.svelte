<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tosd-wbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tosd-wbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-six-solid" {...props}></Icon>
