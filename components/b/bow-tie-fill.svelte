<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln5cit_qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln5cit_qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bow-tie-fill" {...props}></Icon>
