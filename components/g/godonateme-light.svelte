<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktv0erbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ktv0erbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:godonateme-light" {...props}></Icon>
