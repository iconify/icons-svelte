<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aikpq8biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aikpq8biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:note-with-text-fill" {...props}></Icon>
