<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcj42lbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcj42lbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-plus-sharp" {...props}></Icon>
