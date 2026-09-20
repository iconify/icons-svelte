<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcr3pm8qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcr3pm8qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gitignoredotio" {...props}></Icon>
