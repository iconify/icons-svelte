<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb4m6sblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb4m6sblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:form" {...props}></Icon>
