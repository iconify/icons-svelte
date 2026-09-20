<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_ln9i94v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_ln9i94v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-up-large-2-solid" {...props}></Icon>
