<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdp5r-bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdp5r-bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-previous-link" {...props}></Icon>
