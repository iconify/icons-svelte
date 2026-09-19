<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouah7nb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ouah7nb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:font-cursor" {...props}></Icon>
