<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn1rtftuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn1rtftuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jfrog-pipelines" {...props}></Icon>
