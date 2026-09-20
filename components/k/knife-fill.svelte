<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax_-m_bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ax_-m_bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:knife-fill" {...props}></Icon>
