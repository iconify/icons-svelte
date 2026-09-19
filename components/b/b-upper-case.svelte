<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itk3lzbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":735};
const content = `<path class="itk3lzbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:b-upper-case" {...props}></Icon>
