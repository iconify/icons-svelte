<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-ln0mbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":26};
const content = `<path class="f-ln0mbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-presentation-26" {...props}></Icon>
