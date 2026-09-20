<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is5b7bcod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="is5b7bcod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:key-alt-fill" {...props}></Icon>
