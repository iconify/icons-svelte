<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi0b81b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hi0b81b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:phone-off-filled" {...props}></Icon>
