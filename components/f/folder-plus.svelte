<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fap0wgbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fap0wgbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:folder-plus" {...props}></Icon>
