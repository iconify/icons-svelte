<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9fu4zqhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9fu4zqhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:engadget" {...props}></Icon>
