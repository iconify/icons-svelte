<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgxxlhxpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgxxlhxpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-svg" {...props}></Icon>
