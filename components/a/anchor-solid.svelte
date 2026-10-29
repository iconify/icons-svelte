<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apgew5uau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apgew5uau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:anchor-solid" {...props}></Icon>
