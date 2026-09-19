<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnqri_byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fnqri_byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:loadingeight" {...props}></Icon>
