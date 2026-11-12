<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofz-09bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ofz-09bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:azurelogicapps" {...props}></Icon>
