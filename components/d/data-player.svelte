<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx8s2qyca.css';
import '../../css/x/x9g2eubxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yx8s2qyca"/><path class="x9g2eubxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-player" {...props}></Icon>
