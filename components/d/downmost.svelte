<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo35-tb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fo35-tb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:downmost" {...props}></Icon>
