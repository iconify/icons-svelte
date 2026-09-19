<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atljf9blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atljf9blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:luggage-filled" {...props}></Icon>
