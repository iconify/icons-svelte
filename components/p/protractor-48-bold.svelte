<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6q-m_77w.css';
import '../../css/l/l__xd22cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q6q-m_77w"/><path class="l__xd22cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:protractor-48-bold" {...props}></Icon>
