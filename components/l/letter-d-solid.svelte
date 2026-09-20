<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrb84qb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrb84qb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-d-solid" {...props}></Icon>
