<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-m_ziyof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-m_ziyof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nodegui" {...props}></Icon>
