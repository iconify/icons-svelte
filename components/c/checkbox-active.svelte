<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_65xwbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_65xwbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkbox-active" {...props}></Icon>
