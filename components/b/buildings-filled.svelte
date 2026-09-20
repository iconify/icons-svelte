<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a70_mfddy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a70_mfddy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buildings-filled" {...props}></Icon>
