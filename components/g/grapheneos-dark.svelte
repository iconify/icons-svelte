<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrvgcksgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lrvgcksgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grapheneos-dark" {...props}></Icon>
