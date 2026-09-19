<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4x0p8byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4x0p8byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-previous" {...props}></Icon>
