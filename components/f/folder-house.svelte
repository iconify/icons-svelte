<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_5sp8bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c_5sp8bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:folder-house" {...props}></Icon>
