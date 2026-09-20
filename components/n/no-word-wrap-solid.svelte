<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0o1d57if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0o1d57if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:no-word-wrap-solid" {...props}></Icon>
