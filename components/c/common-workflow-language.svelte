<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgxpadckc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgxpadckc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:common-workflow-language" {...props}></Icon>
