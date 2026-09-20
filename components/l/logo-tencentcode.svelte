<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucc5fhbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucc5fhbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tencentcode" {...props}></Icon>
