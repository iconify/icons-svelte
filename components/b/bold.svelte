<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f021dkz6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f021dkz6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bold" {...props}></Icon>
