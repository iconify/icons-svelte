<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqldvs1fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqldvs1fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-schedule" {...props}></Icon>
