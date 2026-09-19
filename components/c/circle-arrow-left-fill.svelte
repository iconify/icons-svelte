<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd738jbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sd738jbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-arrow-left-fill" {...props}></Icon>
