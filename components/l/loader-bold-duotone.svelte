<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql-1g5bil.css';
import '../../css/w/we5rc8m_b.css';
import '../../css/i/igcg0ebrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql-1g5bil"/><path class="we5rc8m_b"/><path class="igcg0ebrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:loader-bold-duotone" {...props}></Icon>
