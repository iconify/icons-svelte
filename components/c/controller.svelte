<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2d15vbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="f2d15vbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:controller" {...props}></Icon>
