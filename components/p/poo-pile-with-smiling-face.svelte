<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1pz6obmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f1pz6obmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:poo-pile-with-smiling-face" {...props}></Icon>
