<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep71wbcll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep71wbcll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-upload" {...props}></Icon>
