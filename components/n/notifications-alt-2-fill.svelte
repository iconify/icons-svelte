<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ful9cebla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ful9cebla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-alt-2-fill" {...props}></Icon>
