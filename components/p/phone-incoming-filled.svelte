<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te0mcgdww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te0mcgdww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:phone-incoming-filled" {...props}></Icon>
