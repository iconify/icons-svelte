<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr5wco3zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fr5wco3zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:log-remove" {...props}></Icon>
