<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai3q__bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai3q__bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:notepadplusplus" {...props}></Icon>
