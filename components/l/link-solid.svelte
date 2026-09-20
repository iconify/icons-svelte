<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6ry8-b9g.css';
import '../../css/t/tyh81m_bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6ry8-b9g"/><path class="tyh81m_bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:link-solid" {...props}></Icon>
