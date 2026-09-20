<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgupo11oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wgupo11oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:csharp" {...props}></Icon>
