<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6kghzene.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="m6kghzene"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:cut-paper" {...props}></Icon>
