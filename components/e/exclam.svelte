<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh823tkng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":77,"height":729};
const content = `<path class="gh823tkng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:exclam" {...props}></Icon>
