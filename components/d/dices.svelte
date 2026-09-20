<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe7nswuwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xe7nswuwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:dices" {...props}></Icon>
