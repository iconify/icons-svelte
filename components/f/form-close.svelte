<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv48bd8ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv48bd8ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-close" {...props}></Icon>
