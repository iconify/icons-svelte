<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm6mt9v_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm6mt9v_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qualtrics" {...props}></Icon>
