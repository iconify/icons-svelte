<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vexo92b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vexo92b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-breadcrumb-filled" {...props}></Icon>
