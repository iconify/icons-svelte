<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7u-_1bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z7u-_1bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:pipeline" {...props}></Icon>
