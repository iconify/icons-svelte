<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcn0yvbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcn0yvbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:gem-c-fill" {...props}></Icon>
