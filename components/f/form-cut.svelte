<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-rnhuohd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-rnhuohd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-cut" {...props}></Icon>
