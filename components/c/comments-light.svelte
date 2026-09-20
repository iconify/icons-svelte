<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaqmwhbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jaqmwhbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:comments-light" {...props}></Icon>
