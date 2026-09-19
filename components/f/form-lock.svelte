<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si-jf7b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si-jf7b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-lock" {...props}></Icon>
