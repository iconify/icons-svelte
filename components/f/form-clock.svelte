<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c06m0hbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c06m0hbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-clock" {...props}></Icon>
