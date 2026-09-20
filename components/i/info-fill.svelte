<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_dczbcun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_dczbcun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:info-fill" {...props}></Icon>
