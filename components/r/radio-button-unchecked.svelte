<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9iqvmbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9iqvmbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:radio-button-unchecked" {...props}></Icon>
