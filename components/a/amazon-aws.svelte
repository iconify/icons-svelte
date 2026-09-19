<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weytb4irw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="weytb4irw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:amazon-aws" {...props}></Icon>
