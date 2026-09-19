<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luse48zfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luse48zfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-add" {...props}></Icon>
