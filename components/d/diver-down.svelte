<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqr5l8bbj.css';
import '../../css/g/gp7kg8iqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="eqr5l8bbj"/><path class="gp7kg8iqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:diver-down" {...props}></Icon>
