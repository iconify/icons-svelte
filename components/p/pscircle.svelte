<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgt-dnbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fgt-dnbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pscircle" {...props}></Icon>
