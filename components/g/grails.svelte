<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws22k8poc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ws22k8poc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:grails" {...props}></Icon>
