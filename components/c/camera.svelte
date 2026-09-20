<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpralsssx.css';
import '../../css/g/gaw19yb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpralsssx"/><path class="gaw19yb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:camera" {...props}></Icon>
