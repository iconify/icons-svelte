<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_2l1bbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m_2l1bbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:cursor-text" {...props}></Icon>
