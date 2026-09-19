<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgd5uubak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sgd5uubak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-zipper" {...props}></Icon>
