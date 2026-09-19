<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo6fs7bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fo6fs7bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-medical-fill" {...props}></Icon>
