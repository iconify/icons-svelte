<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foa7u6bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foa7u6bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:circle-dashed-solid" {...props}></Icon>
