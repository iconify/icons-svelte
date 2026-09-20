<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8t6exbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8t6exbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hangouts" {...props}></Icon>
