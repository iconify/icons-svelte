<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h69_glmrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h69_glmrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:document-add" {...props}></Icon>
