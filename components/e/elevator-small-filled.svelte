<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgmt5_ajv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dgmt5_ajv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:elevator-small-filled" {...props}></Icon>
