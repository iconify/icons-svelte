<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eny1zqvyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eny1zqvyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:mobile-filled" {...props}></Icon>
