<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfoslc4lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jfoslc4lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:present-outline" {...props}></Icon>
