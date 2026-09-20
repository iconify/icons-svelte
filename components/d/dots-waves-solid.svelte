<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvc0acc5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvc0acc5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-waves-solid" {...props}></Icon>
