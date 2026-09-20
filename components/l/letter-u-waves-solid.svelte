<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzrfbxbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzrfbxbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-u-waves-solid" {...props}></Icon>
