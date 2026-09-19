<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdltmv-sf.css';
import '../../css/g/gl2m_3bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdltmv-sf"/><path class="gl2m_3bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-cog-filled" {...props}></Icon>
