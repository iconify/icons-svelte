<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a95-7nkor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a95-7nkor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deepl" {...props}></Icon>
