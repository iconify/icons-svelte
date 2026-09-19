<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svm2kk87j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="svm2kk87j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:humble-bundle" {...props}></Icon>
