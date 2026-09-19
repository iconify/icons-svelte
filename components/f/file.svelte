<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ochfh37om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ochfh37om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file" {...props}></Icon>
