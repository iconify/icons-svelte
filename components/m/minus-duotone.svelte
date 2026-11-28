<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1osvpbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v1osvpbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:minus-duotone" {...props}></Icon>
