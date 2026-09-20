<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om2x0ob5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om2x0ob5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:briefcase-medical" {...props}></Icon>
