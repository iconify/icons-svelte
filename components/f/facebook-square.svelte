<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egtakmbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="egtakmbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:facebook-square" {...props}></Icon>
