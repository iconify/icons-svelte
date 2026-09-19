<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu9iqqbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu9iqqbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:face-smile-solid" {...props}></Icon>
