<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhr__acdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xhr__acdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lungs" {...props}></Icon>
