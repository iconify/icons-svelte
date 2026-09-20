<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdeywbako.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdeywbako"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-code-fill" {...props}></Icon>
