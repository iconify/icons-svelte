<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv3m_437d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hv3m_437d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:audio-outline" {...props}></Icon>
