<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtjdqybjn.css';
import '../../css/n/nhs-d-bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xtjdqybjn"/><path class="nhs-d-bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:bottom-left" {...props}></Icon>
