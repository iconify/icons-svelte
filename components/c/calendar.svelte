<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_58wb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ca_58wb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:calendar" {...props}></Icon>
