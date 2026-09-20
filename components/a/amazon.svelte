<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up97d7kqc.css';
import '../../css/o/or2m_gb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up97d7kqc"/><path class="or2m_gb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:amazon" {...props}></Icon>
