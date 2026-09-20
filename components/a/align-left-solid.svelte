<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7wvzqb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c7wvzqb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:align-left-solid" {...props}></Icon>
