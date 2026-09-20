<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fj6d_hbgz.css';
import '../../css/w/wjltsrbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fj6d_hbgz"/><path class="wjltsrbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-left-square" {...props}></Icon>
