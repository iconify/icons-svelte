<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8nd4gbbc.css';
import '../../css/m/m9thc4yei.css';
import '../../css/j/j_-m04xen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8nd4gbbc"/><path class="m9thc4yei"/><path class="j_-m04xen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:folder" {...props}></Icon>
