<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g52m_vhun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g52m_vhun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:clinical-f-24px" {...props}></Icon>
