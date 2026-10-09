<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7m_sy6ir.css';
import '../../css/q/qmmje9uau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b7m_sy6ir"/><path class="qmmje9uau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioner-20-bold" {...props}></Icon>
