<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yquh6-eyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yquh6-eyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:atom-duotone" {...props}></Icon>
