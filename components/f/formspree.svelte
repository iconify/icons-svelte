<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxa3yccni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxa3yccni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:formspree" {...props}></Icon>
