<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpyq45sbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpyq45sbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-check-sharp" {...props}></Icon>
