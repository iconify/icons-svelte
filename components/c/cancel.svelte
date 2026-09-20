<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w710m_idj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w710m_idj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:cancel" {...props}></Icon>
