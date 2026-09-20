<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv8ezdbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nv8ezdbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:face-smile" {...props}></Icon>
