<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkwxxqb3q.css';
import '../../css/h/hpui6-m_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kkwxxqb3q"/><path class="hpui6-m_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nickel-20-bold" {...props}></Icon>
