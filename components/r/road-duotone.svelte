<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs60qn8ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zs60qn8ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:road-duotone" {...props}></Icon>
