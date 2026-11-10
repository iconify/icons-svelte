<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkw81ac-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dkw81ac-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:boolean-exclude" {...props}></Icon>
