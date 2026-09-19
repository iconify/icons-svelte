<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu8f02jqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xu8f02jqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:face-sad" {...props}></Icon>
