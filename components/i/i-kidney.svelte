<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqvx9zbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jqvx9zbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-kidney" {...props}></Icon>
