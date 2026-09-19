<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmho76qch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gmho76qch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:git-square" {...props}></Icon>
