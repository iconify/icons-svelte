<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xowt0m_af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xowt0m_af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:dialog-16" {...props}></Icon>
