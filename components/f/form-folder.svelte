<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxrd8lbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxrd8lbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-folder" {...props}></Icon>
