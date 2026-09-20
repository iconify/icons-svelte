<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqud1uhki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqud1uhki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-left-circle-solid" {...props}></Icon>
