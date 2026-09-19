<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0gdh4bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r0gdh4bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:maximize-alt-03" {...props}></Icon>
