<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azacryb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="azacryb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-pediatrics" {...props}></Icon>
