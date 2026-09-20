<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7krbcc8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7krbcc8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:flag-finish-alt-light" {...props}></Icon>
