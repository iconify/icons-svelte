<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk_pei11d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk_pei11d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-left-solid" {...props}></Icon>
