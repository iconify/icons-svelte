<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffa_0jn3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffa_0jn3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-alt" {...props}></Icon>
