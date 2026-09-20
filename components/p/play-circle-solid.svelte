<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef4d2rb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef4d2rb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:play-circle-solid" {...props}></Icon>
