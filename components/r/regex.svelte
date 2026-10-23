<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm82hpbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm82hpbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:regex" {...props}></Icon>
