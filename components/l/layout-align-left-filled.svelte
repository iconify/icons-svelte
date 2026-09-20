<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7ddn-9dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7ddn-9dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-align-left-filled" {...props}></Icon>
