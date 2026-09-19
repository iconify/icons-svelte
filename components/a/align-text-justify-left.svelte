<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj8myni9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj8myni9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-text-justify-left" {...props}></Icon>
