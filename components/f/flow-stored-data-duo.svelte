<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqzrm9bdh.css';
import '../../css/u/ur_vkvbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqzrm9bdh secondary"/><path class="primary ur_vkvbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-stored-data-duo" {...props}></Icon>
