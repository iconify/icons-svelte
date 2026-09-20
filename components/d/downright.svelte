<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaazphrqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iaazphrqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:downright" {...props}></Icon>
