<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb6gv4imc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb6gv4imc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:form-validation-cursor-choose" {...props}></Icon>
