<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjyn87vet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wjyn87vet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:male" {...props}></Icon>
