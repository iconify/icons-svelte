<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx3sd2bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx3sd2bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-check-solid" {...props}></Icon>
