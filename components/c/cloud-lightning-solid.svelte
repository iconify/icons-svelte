<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua6xqgsfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua6xqgsfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-lightning-solid" {...props}></Icon>
