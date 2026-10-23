<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg_65gbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg_65gbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grape" {...props}></Icon>
