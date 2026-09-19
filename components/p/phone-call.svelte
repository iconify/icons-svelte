<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t758m_bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t758m_bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:phone-call" {...props}></Icon>
