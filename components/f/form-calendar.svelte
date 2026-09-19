<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn88-3bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn88-3bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-calendar" {...props}></Icon>
