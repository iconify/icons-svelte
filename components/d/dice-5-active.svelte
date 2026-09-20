<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kod3i7btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kod3i7btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-5-active" {...props}></Icon>
