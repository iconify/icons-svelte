<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8ir75bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8ir75bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-x" {...props}></Icon>
