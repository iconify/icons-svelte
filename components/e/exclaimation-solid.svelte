<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avt9bib9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avt9bib9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:exclaimation-solid" {...props}></Icon>
