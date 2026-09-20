<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdxb9g3oh.css';
import '../../css/g/gb0c95-cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdxb9g3oh"/><path class="gb0c95-cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:master-card" {...props}></Icon>
