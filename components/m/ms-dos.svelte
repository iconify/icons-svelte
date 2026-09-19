<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsf314beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":512};
const content = `<path class="nsf314beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ms-dos" {...props}></Icon>
