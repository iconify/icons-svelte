<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ivvcc2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-ivvcc2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-top-filled" {...props}></Icon>
