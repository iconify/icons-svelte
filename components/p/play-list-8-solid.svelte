<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0qwamb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v0qwamb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:play-list-8-solid" {...props}></Icon>
