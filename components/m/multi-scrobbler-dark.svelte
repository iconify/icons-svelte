<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfn1x9uow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfn1x9uow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:multi-scrobbler-dark" {...props}></Icon>
